<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lm5s2311v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lm5s2311v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-left-circle-filled" {...props}></Icon>
