<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bz5obbc_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="bz5obbc_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:cursor-text-small" {...props}></Icon>
