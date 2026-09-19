<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnrq_6d0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnrq_6d0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:people-fill" {...props}></Icon>
