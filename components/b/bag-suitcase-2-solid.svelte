<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2n5-jbna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="p2n5-jbna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:bag-suitcase-2-solid" {...props}></Icon>
