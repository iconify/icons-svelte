<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxz2te--u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qxz2te--u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:folder-solid" {...props}></Icon>
