<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kllrszb1h.css';
import '../../css/k/kknmzu6wn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kllrszb1h"/><path class="kknmzu6wn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:or-gate-48-bold" {...props}></Icon>
