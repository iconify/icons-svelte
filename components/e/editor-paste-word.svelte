<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sobudmbdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sobudmbdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:editor-paste-word" {...props}></Icon>
