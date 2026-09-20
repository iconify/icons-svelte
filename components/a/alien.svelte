<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqs1aq2hm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mqs1aq2hm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:alien" {...props}></Icon>
