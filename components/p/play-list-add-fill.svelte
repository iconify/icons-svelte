<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2x5blw9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i2x5blw9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:play-list-add-fill" {...props}></Icon>
