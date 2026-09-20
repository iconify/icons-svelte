<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4uwu8bbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v4uwu8bbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:jetpack-compose" {...props}></Icon>
