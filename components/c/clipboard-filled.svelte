<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-5q-ebnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j-5q-ebnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:clipboard-filled" {...props}></Icon>
