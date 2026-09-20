<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-cra3-wf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-cra3-wf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:folder-hold-bold" {...props}></Icon>
