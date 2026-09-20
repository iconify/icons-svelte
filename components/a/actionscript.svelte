<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3nu1cc-n.css';
import '../../css/m/m7_384bcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":960,"top":-960};
const content = `<path class="s3nu1cc-n"/><path class="m7_384bcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:actionscript" {...props}></Icon>
