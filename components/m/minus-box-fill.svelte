<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdbp7xbqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="fdbp7xbqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:minus-box-fill" {...props}></Icon>
