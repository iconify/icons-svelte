<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrmddmjov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qrmddmjov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:message-minus-round-fill" {...props}></Icon>
