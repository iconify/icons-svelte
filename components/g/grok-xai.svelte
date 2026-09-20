<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idfr6hb-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="idfr6hb-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:grok-xai" {...props}></Icon>
