<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q488z71gd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q488z71gd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:claude-fill" {...props}></Icon>
