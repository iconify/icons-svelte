<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4vb5lb2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i4vb5lb2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-forbid-fill" {...props}></Icon>
