<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgb4m8j_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hgb4m8j_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:group" {...props}></Icon>
