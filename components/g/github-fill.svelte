<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oesj0egjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oesj0egjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:github-fill" {...props}></Icon>
