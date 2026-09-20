<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jb7cp-bpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jb7cp-bpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:north-west-square-line" {...props}></Icon>
