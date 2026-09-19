<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ci5k5y4ca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ci5k5y4ca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:input-numbers-filled" {...props}></Icon>
