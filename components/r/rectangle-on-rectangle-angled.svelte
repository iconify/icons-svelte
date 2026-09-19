<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie7tk9bnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ie7tk9bnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:rectangle-on-rectangle-angled" {...props}></Icon>
