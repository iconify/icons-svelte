<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lu2l__qdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lu2l__qdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:phonecall-blocked-outline" {...props}></Icon>
