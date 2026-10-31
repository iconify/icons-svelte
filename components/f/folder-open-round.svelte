<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqv0rlgud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fqv0rlgud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:folder-open-round" {...props}></Icon>
