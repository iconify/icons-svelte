<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfl4o4bxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wfl4o4bxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:phone" {...props}></Icon>
