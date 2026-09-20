<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b10nt4bic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b10nt4bic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:elm" {...props}></Icon>
