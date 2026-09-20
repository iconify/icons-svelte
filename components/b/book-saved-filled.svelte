<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqv5sccyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bqv5sccyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:book-saved-filled" {...props}></Icon>
