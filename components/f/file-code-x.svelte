<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9jygtzdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b9jygtzdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:file-code-x" {...props}></Icon>
