<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djo0k6nzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="djo0k6nzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:play-small-solid" {...props}></Icon>
