<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/et7yk-bun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="et7yk-bun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:highlights" {...props}></Icon>
