<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fr31whbaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fr31whbaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:rectangle-2" {...props}></Icon>
