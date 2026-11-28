<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fu_p-r0dn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fu_p-r0dn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:helmet" {...props}></Icon>
