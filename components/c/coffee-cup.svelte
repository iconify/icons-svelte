<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/joc0uylro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="joc0uylro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:coffee-cup" {...props}></Icon>
