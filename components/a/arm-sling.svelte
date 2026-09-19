<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_oc2ubbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a_oc2ubbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:arm-sling" {...props}></Icon>
