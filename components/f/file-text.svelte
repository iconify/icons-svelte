<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qi3v-fbxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1792};
const content = `<path class="qi3v-fbxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:file-text" {...props}></Icon>
