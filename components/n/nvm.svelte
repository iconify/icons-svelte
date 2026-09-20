<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu7bl6bxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vu7bl6bxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:nvm" {...props}></Icon>
