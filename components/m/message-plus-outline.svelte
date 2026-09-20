<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qevooufdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qevooufdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:message-plus-outline" {...props}></Icon>
