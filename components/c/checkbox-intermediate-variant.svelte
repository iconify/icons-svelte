<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ng7w36b3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="ng7w36b3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:checkbox-intermediate-variant" {...props}></Icon>
