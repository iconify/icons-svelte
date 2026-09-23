<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzw-n1jqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gzw-n1jqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:file-audio-sharp-fill" {...props}></Icon>
