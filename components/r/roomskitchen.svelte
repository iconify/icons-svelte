<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v--3-qaeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v--3-qaeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:roomskitchen" {...props}></Icon>
