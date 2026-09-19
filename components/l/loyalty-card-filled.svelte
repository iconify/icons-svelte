<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ih7o_lvei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ih7o_lvei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:loyalty-card-filled" {...props}></Icon>
