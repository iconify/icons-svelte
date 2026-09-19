<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4_6zfl5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c4_6zfl5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:lotion" {...props}></Icon>
