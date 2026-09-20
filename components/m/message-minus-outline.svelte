<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtk_9ha-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qtk_9ha-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:message-minus-outline" {...props}></Icon>
