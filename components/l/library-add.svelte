<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/id0lu2odl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="id0lu2odl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:library-add" {...props}></Icon>
