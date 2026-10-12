<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbyoeqbxo.css';
import '../../css/v/vp_3b7bmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kbyoeqbxo"/><path class="vp_3b7bmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:plunger-20" {...props}></Icon>
