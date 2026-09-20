<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nclo1ib8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nclo1ib8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bug" {...props}></Icon>
