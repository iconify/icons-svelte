<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ui968qbnt.css';
import '../../css/u/u-wijubjh.css';
import '../../css/b/bf8rmdbee.css';
import '../../css/k/kaxml2b1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ui968qbnt"/><path class="u-wijubjh"/><path class="bf8rmdbee"/><path class="kaxml2b1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-symbol-20-bold" {...props}></Icon>
