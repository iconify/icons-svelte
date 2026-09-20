<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyf99sf2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fyf99sf2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:credit-card-remove" {...props}></Icon>
