<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gte1b_zmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gte1b_zmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:contract-outline" {...props}></Icon>
