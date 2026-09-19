<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q026oo9wp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q026oo9wp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:chat-option" {...props}></Icon>
