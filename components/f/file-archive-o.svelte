<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6o8szbwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1792};
const content = `<path class="o6o8szbwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:file-archive-o" {...props}></Icon>
