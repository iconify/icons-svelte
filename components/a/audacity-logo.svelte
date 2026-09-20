<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbufax35a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fbufax35a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:audacity-logo" {...props}></Icon>
