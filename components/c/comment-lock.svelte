<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfth42hyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jfth42hyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:comment-lock" {...props}></Icon>
