<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0ckwz-hc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n0ckwz-hc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:plus-circle-fill" {...props}></Icon>
