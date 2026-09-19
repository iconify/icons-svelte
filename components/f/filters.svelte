<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz71u99bq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oz71u99bq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:filters" {...props}></Icon>
