<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ma7frebpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ma7frebpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:3-minus" {...props}></Icon>
