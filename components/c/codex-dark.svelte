<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtyomgb2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gtyomgb2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:codex-dark" {...props}></Icon>
