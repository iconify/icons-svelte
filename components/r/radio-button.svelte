<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmza4pb7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qmza4pb7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:radio-button" {...props}></Icon>
