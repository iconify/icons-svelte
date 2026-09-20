<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q00slbc9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q00slbc9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:check" {...props}></Icon>
