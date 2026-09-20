<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4gcrl_ib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o4gcrl_ib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:done-light" {...props}></Icon>
