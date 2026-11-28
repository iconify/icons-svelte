<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajqbxzbxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ajqbxzbxv primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-up-to-line-duotone" {...props}></Icon>
