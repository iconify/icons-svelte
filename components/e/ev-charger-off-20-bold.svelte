<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u52a-ibck.css';
import '../../css/j/jhwn4fbsd.css';
import '../../css/q/qmmb_82ud.css';
import '../../css/u/ui-ddfl2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u52a-ibck"/><path class="jhwn4fbsd"/><path class="qmmb_82ud"/><path class="ui-ddfl2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ev-charger-off-20-bold" {...props}></Icon>
