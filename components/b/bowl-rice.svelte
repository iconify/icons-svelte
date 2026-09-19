<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7i1l88xv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c7i1l88xv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bowl-rice" {...props}></Icon>
