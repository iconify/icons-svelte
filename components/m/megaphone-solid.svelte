<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slqn7pbsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="slqn7pbsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:megaphone-solid" {...props}></Icon>
