<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6bhsac-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c6bhsac-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:codex-light" {...props}></Icon>
