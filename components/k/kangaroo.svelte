<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9l22sefq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o9l22sefq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:kangaroo" {...props}></Icon>
