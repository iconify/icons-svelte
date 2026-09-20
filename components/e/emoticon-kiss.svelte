<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o86ll_bsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o86ll_bsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:emoticon-kiss" {...props}></Icon>
