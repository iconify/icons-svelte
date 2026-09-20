<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_8xdqbcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p_8xdqbcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:restart-circle-bold" {...props}></Icon>
