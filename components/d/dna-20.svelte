<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spkjwsbgk.css';
import '../../css/f/fr-v3dbag.css';
import '../../css/r/rbkzkvmvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="spkjwsbgk"/><path class="fr-v3dbag"/><path class="rbkzkvmvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dna-20" {...props}></Icon>
