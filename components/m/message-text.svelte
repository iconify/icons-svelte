<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elsly3bbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="elsly3bbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:message-text" {...props}></Icon>
