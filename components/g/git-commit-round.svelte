<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knui3cfem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="knui3cfem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:git-commit-round" {...props}></Icon>
