<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udwer-bvl.css';
import '../../css/j/jcdaq3bjh.css';
import '../../css/a/a4d54xg-r.css';
import '../../css/d/du3a-kbxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="udwer-bvl"/><path class="jcdaq3bjh"/><path class="a4d54xg-r"/><path class="du3a-kbxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:crutch-48-bold" {...props}></Icon>
