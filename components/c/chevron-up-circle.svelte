<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ro1fyrkqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ro1fyrkqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:chevron-up-circle" {...props}></Icon>
