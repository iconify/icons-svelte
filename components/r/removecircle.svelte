<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhu91hmvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="dhu91hmvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:removecircle" {...props}></Icon>
