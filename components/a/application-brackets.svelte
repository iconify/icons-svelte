<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oo1rknb5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oo1rknb5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:application-brackets" {...props}></Icon>
