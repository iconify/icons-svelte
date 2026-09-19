<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjkt4fvdh.css';
import '../../css/j/jswt5rbrt.css';
import '../../css/u/um2_m_i-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bjkt4fvdh"/><path class="jswt5rbrt"/><path class="um2_m_i-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-bug" {...props}></Icon>
