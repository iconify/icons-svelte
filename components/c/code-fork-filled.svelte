<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvwkpzauj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uvwkpzauj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:code-fork-filled" {...props}></Icon>
