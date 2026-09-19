<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ur-ntnenv.css';
import '../../css/k/kgjor1bvy.css';
import '../../css/h/hakimgbod.css';
import '../../css/p/p9b78ab8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ur-ntnenv"/><path class="kgjor1bvy"/><path class="hakimgbod"/><path class="p9b78ab8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:full-trash" {...props}></Icon>
