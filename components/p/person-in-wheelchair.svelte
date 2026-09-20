<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyrfhsqar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nyrfhsqar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-in-wheelchair" {...props}></Icon>
