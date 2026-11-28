<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yav09-brf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yav09-brf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:inbox-x" {...props}></Icon>
