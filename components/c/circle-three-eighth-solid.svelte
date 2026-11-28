<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bf1qxsb6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bf1qxsb6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:circle-three-eighth-solid" {...props}></Icon>
