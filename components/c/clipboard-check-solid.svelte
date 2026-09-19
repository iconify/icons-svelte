<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-xxz-ihp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d-xxz-ihp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:clipboard-check-solid" {...props}></Icon>
