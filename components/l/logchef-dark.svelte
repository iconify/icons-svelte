<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a82ao3b6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a82ao3b6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:logchef-dark" {...props}></Icon>
