<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_f-9jb_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v_f-9jb_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:git-commit-sharp" {...props}></Icon>
