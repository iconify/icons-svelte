<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2__pti2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g2__pti2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chevron-right-double" {...props}></Icon>
