<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2-u_vb7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x2-u_vb7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:chevron-up-outline" {...props}></Icon>
