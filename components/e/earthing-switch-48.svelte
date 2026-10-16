<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2o-q5bqy.css';
import '../../css/v/v51dofb5w.css';
import '../../css/r/rsiohj6qn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c2o-q5bqy"/><path class="v51dofb5w"/><path class="rsiohj6qn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:earthing-switch-48" {...props}></Icon>
