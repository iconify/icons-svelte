<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8ude0bub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="m8ude0bub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:chevron-up" {...props}></Icon>
