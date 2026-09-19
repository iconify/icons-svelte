<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-cmvybdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p-cmvybdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:paper-plane-solid" {...props}></Icon>
