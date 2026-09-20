<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e018eoaqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e018eoaqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brightness-up" {...props}></Icon>
