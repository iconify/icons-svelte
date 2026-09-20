<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttvm6jbzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ttvm6jbzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:megaphone-2-solid" {...props}></Icon>
