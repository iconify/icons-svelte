<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a__i1hb1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a__i1hb1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:lemon-solid" {...props}></Icon>
