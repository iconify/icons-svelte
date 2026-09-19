<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwm7a-bih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iwm7a-bih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:database-outline" {...props}></Icon>
