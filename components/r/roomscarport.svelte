<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iu6zwruqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iu6zwruqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:roomscarport" {...props}></Icon>
