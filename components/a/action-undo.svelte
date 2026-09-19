<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnht1tg6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qnht1tg6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:action-undo" {...props}></Icon>
