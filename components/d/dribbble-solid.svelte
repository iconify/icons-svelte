<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nswitfr9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nswitfr9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:dribbble-solid" {...props}></Icon>
