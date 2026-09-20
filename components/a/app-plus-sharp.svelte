<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpoekowgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vpoekowgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:app-plus-sharp" {...props}></Icon>
