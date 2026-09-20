<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhjllqb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="bhjllqb5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:format-align-left" {...props}></Icon>
