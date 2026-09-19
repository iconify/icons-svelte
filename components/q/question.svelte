<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4n1yqnky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j4n1yqnky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:question" {...props}></Icon>
