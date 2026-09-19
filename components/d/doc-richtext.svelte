<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9uf7gbnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="q9uf7gbnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:doc-richtext" {...props}></Icon>
