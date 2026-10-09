<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fm-6ijbqa.css';
import '../../css/k/k3_wrxi7z.css';
import '../../css/d/d90gdxket.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fm-6ijbqa"/><path class="k3_wrxi7z"/><path class="d90gdxket"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:jack-up-vessel-48" {...props}></Icon>
