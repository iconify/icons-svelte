<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3x7q5b1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p3x7q5b1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:hide-sidebar" {...props}></Icon>
