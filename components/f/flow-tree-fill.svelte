<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpc22hbyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hpc22hbyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:flow-tree-fill" {...props}></Icon>
