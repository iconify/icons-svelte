<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jb8gpab0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jb8gpab0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:endpoints" {...props}></Icon>
