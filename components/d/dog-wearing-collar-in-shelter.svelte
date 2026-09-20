<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4gv7gz6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="q4gv7gz6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:dog-wearing-collar-in-shelter" {...props}></Icon>
