<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/voicgi8vf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="voicgi8vf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:connectivity" {...props}></Icon>
