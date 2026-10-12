<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9v47kbel.css';
import '../../css/e/e8kp6ybjw.css';
import '../../css/o/o9b-4cbec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="q9v47kbel"/><path class="e8kp6ybjw"/><path class="o9b-4cbec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:directions-48" {...props}></Icon>
