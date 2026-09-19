<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgg0ddbbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fgg0ddbbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:movies-anywhere-text" {...props}></Icon>
