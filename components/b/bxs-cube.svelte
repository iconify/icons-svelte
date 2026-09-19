<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fr9ofrbkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fr9ofrbkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-cube" {...props}></Icon>
