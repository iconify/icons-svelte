<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pac7fn7hq.css';
import '../../css/g/gl2fr07us.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pac7fn7hq"/><path class="gl2fr07us"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:houses-2-filled" {...props}></Icon>
