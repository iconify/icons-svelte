<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cm8xpob-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cm8xpob-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:icecream" {...props}></Icon>
