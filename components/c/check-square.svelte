<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8galqbfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n8galqbfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:check-square" {...props}></Icon>
