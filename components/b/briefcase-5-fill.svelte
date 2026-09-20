<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibf9d8bse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ibf9d8bse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:briefcase-5-fill" {...props}></Icon>
