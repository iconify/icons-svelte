<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uimkucb6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uimkucb6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:blur-alt-filled" {...props}></Icon>
