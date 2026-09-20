<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt8n-9b6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="jt8n-9b6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:border-top-left-right" {...props}></Icon>
