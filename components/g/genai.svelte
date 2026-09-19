<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a025csbqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path xmlns="http://www.w3.org/2000/svg" class="a025csbqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:genai" {...props}></Icon>
