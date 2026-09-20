<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lb8_5bccr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lb8_5bccr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:distribute-vertical-outline" {...props}></Icon>
