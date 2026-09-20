<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eraxdg7iz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="eraxdg7iz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:compass-west-arrow" {...props}></Icon>
