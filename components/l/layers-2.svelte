<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3es_9_li.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d3es_9_li"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:layers-2" {...props}></Icon>
