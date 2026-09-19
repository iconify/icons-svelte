<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mov5x5atu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="mov5x5atu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:phone-square" {...props}></Icon>
