<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cq6l3ibbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cq6l3ibbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:acala" {...props}></Icon>
