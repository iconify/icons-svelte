<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihk4kgyae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ihk4kgyae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:lightbulb-solid" {...props}></Icon>
