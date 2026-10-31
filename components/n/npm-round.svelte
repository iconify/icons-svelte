<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv9tpdbaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pv9tpdbaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:npm-round" {...props}></Icon>
