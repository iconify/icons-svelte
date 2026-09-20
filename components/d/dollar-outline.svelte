<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i923-abes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="i923-abes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:dollar-outline" {...props}></Icon>
