<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ju6tnpb4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ju6tnpb4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:question-mark" {...props}></Icon>
