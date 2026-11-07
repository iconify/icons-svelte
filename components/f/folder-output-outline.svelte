<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjgv7_b4e.css';
import '../../css/f/f4kwoxb6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jjgv7_b4e"/><path class="f4kwoxb6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-output-outline" {...props}></Icon>
