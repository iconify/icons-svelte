<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llvmp7gcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="llvmp7gcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-align-offset-top-fill" {...props}></Icon>
