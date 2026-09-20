<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zi8hcxn_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zi8hcxn_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:plus-minus" {...props}></Icon>
