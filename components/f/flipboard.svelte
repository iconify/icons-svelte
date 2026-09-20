<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9k7zhbiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w9k7zhbiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:flipboard" {...props}></Icon>
