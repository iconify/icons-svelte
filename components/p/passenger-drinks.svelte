<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkohjf76e.css';
import '../../css/i/it25zdp1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kkohjf76e"/><path class="it25zdp1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:passenger-drinks" {...props}></Icon>
