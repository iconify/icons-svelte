<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7daet4tt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="n7daet4tt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:github" {...props}></Icon>
