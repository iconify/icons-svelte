<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob03obcjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ob03obcjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ikea-gunnarp-panel" {...props}></Icon>
