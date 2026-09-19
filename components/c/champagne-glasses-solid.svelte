<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or7pjbbqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="or7pjbbqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:champagne-glasses-solid" {...props}></Icon>
