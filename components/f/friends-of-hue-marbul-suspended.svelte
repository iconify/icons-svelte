<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6i8fxkqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u6i8fxkqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:friends-of-hue-marbul-suspended" {...props}></Icon>
