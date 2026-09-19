<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kg3ptdbld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":662};
const content = `<path class="kg3ptdbld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:paint" {...props}></Icon>
