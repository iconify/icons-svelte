<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p71oiqb6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p71oiqb6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:ordored-list-solid" {...props}></Icon>
