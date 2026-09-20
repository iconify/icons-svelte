<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgn4b_b9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jgn4b_b9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:folder-filled-24" {...props}></Icon>
