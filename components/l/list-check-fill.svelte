<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a52r8v9zd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a52r8v9zd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:list-check-fill" {...props}></Icon>
