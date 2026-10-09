<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewn1ke3br.css';
import '../../css/n/nthzzhwxx.css';
import '../../css/p/pufh2ab9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ewn1ke3br"/><path class="nthzzhwxx"/><path class="pufh2ab9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:layout-20" {...props}></Icon>
