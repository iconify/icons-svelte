<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie0e-hgta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ie0e-hgta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:message-text" {...props}></Icon>
