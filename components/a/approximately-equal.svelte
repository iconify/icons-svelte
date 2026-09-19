<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1uu-d19c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t1uu-d19c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:approximately-equal" {...props}></Icon>
