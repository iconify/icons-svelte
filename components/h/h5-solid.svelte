<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or1fcgb_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="or1fcgb_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:h5-solid" {...props}></Icon>
