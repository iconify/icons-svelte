<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cn1nskbla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cn1nskbla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:html-solid" {...props}></Icon>
