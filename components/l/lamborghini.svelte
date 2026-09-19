<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml18xit3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ml18xit3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:lamborghini" {...props}></Icon>
