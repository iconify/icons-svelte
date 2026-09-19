<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epj4bbkgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="epj4bbkgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:indent-solid" {...props}></Icon>
