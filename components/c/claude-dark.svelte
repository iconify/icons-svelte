<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbti06zra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mbti06zra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:claude-dark" {...props}></Icon>
