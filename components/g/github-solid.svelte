<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wex9syf4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wex9syf4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:github-solid" {...props}></Icon>
