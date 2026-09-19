<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxbqhgb_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="attachment-clip-outline"><path class="Vector wxbqhgb_a" clip-rule="evenodd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:attachment-clip-outline" {...props}></Icon>
