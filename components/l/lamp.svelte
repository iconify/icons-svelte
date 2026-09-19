<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdup9ob0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jdup9ob0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:lamp" {...props}></Icon>
