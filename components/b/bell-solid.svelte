<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odcfwjbjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="odcfwjbjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:bell-solid" {...props}></Icon>
