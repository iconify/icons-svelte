<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axz7gbckk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="axz7gbckk primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:maximize-duotone" {...props}></Icon>
