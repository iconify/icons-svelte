<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qo1_vnkyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qo1_vnkyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-down-3-square-thin" {...props}></Icon>
