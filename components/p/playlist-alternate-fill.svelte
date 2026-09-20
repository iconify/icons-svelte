<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igg6x_b9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="igg6x_b9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:playlist-alternate-fill" {...props}></Icon>
