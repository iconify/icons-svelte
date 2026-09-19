<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4byp0l9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u4byp0l9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:check-verified" {...props}></Icon>
