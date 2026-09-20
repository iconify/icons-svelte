<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhuug4b4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bhuug4b4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:phone-outline" {...props}></Icon>
