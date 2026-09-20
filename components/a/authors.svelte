<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9bbvbbxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k9bbvbbxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:authors" {...props}></Icon>
