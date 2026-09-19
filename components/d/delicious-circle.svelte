<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4j8ruk9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="d4j8ruk9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:delicious-circle" {...props}></Icon>
