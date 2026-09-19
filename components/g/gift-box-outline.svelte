<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6-vpyb8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f6-vpyb8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:gift-box-outline" {...props}></Icon>
