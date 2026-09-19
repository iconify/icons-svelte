<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwx73ffxg.css';
import '../../css/e/egqw4un5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kwx73ffxg"/><path class="egqw4un5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:openfolder" {...props}></Icon>
