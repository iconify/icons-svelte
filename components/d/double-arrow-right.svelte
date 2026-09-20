<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpjsjubje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gpjsjubje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:double-arrow-right" {...props}></Icon>
