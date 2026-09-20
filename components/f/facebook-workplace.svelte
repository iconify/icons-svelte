<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dajbc_bbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dajbc_bbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:facebook-workplace" {...props}></Icon>
