<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpno0ub3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dpno0ub3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:keyboard" {...props}></Icon>
