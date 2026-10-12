<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwnv2zbmo.css';
import '../../css/q/q0rdytb4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jwnv2zbmo"/><path class="q0rdytb4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:frog-20-bold" {...props}></Icon>
