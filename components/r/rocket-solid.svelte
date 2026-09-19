<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jddxo1boq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jddxo1boq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:rocket-solid" {...props}></Icon>
