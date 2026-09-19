<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km82hcy6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="km82hcy6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:caption-outline" {...props}></Icon>
