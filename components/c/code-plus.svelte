<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6q3gcbvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k6q3gcbvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:code-plus" {...props}></Icon>
