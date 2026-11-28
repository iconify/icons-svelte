<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5a5l6b1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o5a5l6b1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:message-dots-check" {...props}></Icon>
