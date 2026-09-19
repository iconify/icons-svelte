<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qr4es86yo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qr4es86yo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:layout-columns" {...props}></Icon>
