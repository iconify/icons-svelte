<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skc1_tbgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="skc1_tbgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:eye-off-filled" {...props}></Icon>
