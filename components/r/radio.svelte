<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxpz6x56l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxpz6x56l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:radio" {...props}></Icon>
