<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aaqzw85bx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aaqzw85bx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:git" {...props}></Icon>
