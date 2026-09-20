<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8vp84fum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5,"top":-2};
const content = `<path class="i8vp84fum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:female" {...props}></Icon>
