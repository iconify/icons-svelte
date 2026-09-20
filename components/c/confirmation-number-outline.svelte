<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hydikxbft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hydikxbft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:confirmation-number-outline" {...props}></Icon>
