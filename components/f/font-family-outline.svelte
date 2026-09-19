<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/du7zlccih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="du7zlccih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:font-family-outline" {...props}></Icon>
