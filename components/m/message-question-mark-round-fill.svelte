<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx450s6ch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hx450s6ch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:message-question-mark-round-fill" {...props}></Icon>
