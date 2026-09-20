<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvzur6duk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="tvzur6duk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:apps-box-fill" {...props}></Icon>
