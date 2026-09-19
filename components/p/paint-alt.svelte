<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jf6rg8q0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jf6rg8q0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:paint-alt" {...props}></Icon>
