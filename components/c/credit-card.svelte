<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/roquk4b2w.css';
import '../../css/t/tba9ohb5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="roquk4b2w"/><path class="tba9ohb5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:credit-card" {...props}></Icon>
