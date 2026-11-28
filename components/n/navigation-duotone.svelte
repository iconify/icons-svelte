<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cya9mgwew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cya9mgwew primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:navigation-duotone" {...props}></Icon>
