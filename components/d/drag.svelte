<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvge1vtpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zvge1vtpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:drag" {...props}></Icon>
