<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9ohr9txj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="s9ohr9txj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:id-badge" {...props}></Icon>
