<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6mc35b_l.css';
import '../../css/o/ofxcalb1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i6mc35b_l"/><path class="ofxcalb1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bonfire-48-bold" {...props}></Icon>
