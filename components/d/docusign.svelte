<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rna3pxbiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rna3pxbiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:docusign" {...props}></Icon>
