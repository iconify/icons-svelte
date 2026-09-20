<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp08p-bxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="bp08p-bxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:bug" {...props}></Icon>
