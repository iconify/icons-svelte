<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlhyu9but.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jlhyu9but"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:letters-b" {...props}></Icon>
