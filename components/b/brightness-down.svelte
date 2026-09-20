<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/excfc4j-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="excfc4j-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brightness-down" {...props}></Icon>
