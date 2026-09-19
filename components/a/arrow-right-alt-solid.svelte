<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slxx8490d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="slxx8490d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:arrow-right-alt-solid" {...props}></Icon>
