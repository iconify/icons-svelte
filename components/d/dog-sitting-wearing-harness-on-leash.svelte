<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzw_ce6aq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tzw_ce6aq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:dog-sitting-wearing-harness-on-leash" {...props}></Icon>
