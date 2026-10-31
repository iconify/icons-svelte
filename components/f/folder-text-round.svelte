<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stetxqbsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="stetxqbsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:folder-text-round" {...props}></Icon>
