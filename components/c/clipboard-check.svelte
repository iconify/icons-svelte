<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/il9_oqnbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="il9_oqnbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:clipboard-check" {...props}></Icon>
