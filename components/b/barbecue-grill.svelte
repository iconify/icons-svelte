<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3jbr2e9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v3jbr2e9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:barbecue-grill" {...props}></Icon>
