<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1qr2z6ci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="reorder-outline"><path class="Vector o1qr2z6ci"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:reorder-outline" {...props}></Icon>
