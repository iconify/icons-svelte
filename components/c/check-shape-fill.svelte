<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ej82teboy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ej82teboy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:check-shape-fill" {...props}></Icon>
