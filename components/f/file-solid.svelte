<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5wh2ubgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u5wh2ubgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:file-solid" {...props}></Icon>
