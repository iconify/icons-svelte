<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfk9ubm9c.css';
import '../../css/x/xe9uj2srj.css';
import '../../css/g/gvyjhvf0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="jfk9ubm9c"/><circle class="xe9uj2srj"/><path class="gvyjhvf0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:list-bulleted" {...props}></Icon>
