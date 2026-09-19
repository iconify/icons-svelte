<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd93lvb4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jd93lvb4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:arrow-long-left-r" {...props}></Icon>
