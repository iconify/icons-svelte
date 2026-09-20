<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqg7_db4w.css';
import '../../css/f/frhmf7-sb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bqg7_db4w"/><path class="frhmf7-sb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:file-zip-24" {...props}></Icon>
