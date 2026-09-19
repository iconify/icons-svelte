<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx8ztij1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lx8ztij1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:dots-vertical-outline" {...props}></Icon>
