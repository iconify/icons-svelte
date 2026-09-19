<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/ve0ln5b7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ve0ln5b7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:direwolf" {...props}></Icon>
