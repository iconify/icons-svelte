<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtqwdrb6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jtqwdrb6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:habitica-light" {...props}></Icon>
