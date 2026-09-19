<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgpqfv2kb.css';
import '../../css/p/pp7u04bjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qgpqfv2kb"/><path class="pp7u04bjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:alarm-outline" {...props}></Icon>
