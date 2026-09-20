<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i38sq8d7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i38sq8d7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:align-bottom-detailed-line" {...props}></Icon>
