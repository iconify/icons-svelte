<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1l_6cc3h.css';
import '../../css/o/oxijutbgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":24};
const content = `<path class="e1l_6cc3h"/><path class="oxijutbgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:pulse" {...props}></Icon>
