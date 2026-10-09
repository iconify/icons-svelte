<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqul4gkqk.css';
import '../../css/u/u7bozsa8i.css';
import '../../css/t/tkxry7wol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zqul4gkqk"/><path class="u7bozsa8i"/><path class="tkxry7wol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flywheel-48" {...props}></Icon>
