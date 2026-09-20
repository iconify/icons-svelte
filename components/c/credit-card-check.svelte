<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmn53fb3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rmn53fb3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:credit-card-check" {...props}></Icon>
