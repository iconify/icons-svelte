<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbd9pswha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jbd9pswha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:comment-exclamation" {...props}></Icon>
