<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-qdqubtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="b-qdqubtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:asciidoctor" {...props}></Icon>
