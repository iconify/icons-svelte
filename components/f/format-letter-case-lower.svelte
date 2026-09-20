<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_u6k5bzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_u6k5bzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-letter-case-lower" {...props}></Icon>
