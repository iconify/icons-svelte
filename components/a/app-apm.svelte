<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krpjbebjv.css';
import '../../css/k/krmzf_byg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="krpjbebjv"/><path class="krmzf_byg ouiIcon__fillSecondary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:app-apm" {...props}></Icon>
