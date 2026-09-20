<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hi44x2b4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hi44x2b4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:code-scan" {...props}></Icon>
