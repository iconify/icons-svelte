<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ruy1hxbwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ruy1hxbwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:dice-solid" {...props}></Icon>
