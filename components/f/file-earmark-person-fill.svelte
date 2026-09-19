<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0fztwm7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l0fztwm7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:file-earmark-person-fill" {...props}></Icon>
