<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4s-ztb6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f4s-ztb6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:claude-code" {...props}></Icon>
