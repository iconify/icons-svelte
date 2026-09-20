<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8kcr9bvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="p8kcr9bvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:label-variant" {...props}></Icon>
