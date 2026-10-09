<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2dc9v3fg.css';
import '../../css/j/jwps220zj.css';
import '../../css/b/bdd_6-bdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x2dc9v3fg"/><path class="jwps220zj"/><path class="bdd_6-bdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:crew-transfer-vessel-48-bold" {...props}></Icon>
