<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9xvnhbhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="o9xvnhbhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:kanji-utage" {...props}></Icon>
