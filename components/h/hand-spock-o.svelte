<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nst4do0bf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1920,"height":1792};
const content = `<path class="nst4do0bf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:hand-spock-o" {...props}></Icon>
