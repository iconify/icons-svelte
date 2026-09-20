<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqn8xlbnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aqn8xlbnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-upload-line" {...props}></Icon>
