<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1aqwe6-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a1aqwe6-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:rotate-smartphone" {...props}></Icon>
