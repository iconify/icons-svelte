<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-wmgc9rj.css';
import '../../css/i/i23da44dj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e-wmgc9rj"/><path class="i23da44dj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:lighthouse-filled" {...props}></Icon>
