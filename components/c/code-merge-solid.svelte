<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-ikz9bal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w-ikz9bal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:code-merge-solid" {...props}></Icon>
