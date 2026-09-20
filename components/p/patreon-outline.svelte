<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lga-v6l8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lga-v6l8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:patreon-outline" {...props}></Icon>
