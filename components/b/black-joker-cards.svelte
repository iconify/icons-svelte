<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfy1-wbfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="lfy1-wbfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:black-joker-cards" {...props}></Icon>
