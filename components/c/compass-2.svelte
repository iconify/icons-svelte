<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-2j-zbrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j-2j-zbrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:compass-2" {...props}></Icon>
