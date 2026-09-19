<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekt9y_bzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ekt9y_bzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:location-pin-minus" {...props}></Icon>
