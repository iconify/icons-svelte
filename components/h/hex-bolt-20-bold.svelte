<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xerqgrbub.css';
import '../../css/a/audsyabir.css';
import '../../css/v/v6pfx7zrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xerqgrbub"/><path class="audsyabir"/><path class="v6pfx7zrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hex-bolt-20-bold" {...props}></Icon>
