<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mncvsnb5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mncvsnb5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:robinhood" {...props}></Icon>
