<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1fdsqbxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c1fdsqbxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:dissatisfaction-filled" {...props}></Icon>
