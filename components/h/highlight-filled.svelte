<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgvoz-bla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qgvoz-bla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:highlight-filled" {...props}></Icon>
