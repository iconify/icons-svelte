<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehc2xkc2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ehc2xkc2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:directtv" {...props}></Icon>
