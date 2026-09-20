<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnr4hs01v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mnr4hs01v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:microsoftvisio" {...props}></Icon>
