<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k07zhnbwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k07zhnbwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:globe-solid" {...props}></Icon>
