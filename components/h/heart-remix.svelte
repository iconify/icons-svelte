<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9cj6lb5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="d9cj6lb5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:heart-remix" {...props}></Icon>
