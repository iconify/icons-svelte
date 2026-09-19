<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bu6p_sb1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":705,"height":1024};
const content = `<path class="bu6p_sb1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:heavymetal" {...props}></Icon>
