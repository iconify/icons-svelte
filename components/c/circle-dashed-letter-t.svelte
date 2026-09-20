<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvp-9fuxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jvp-9fuxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-dashed-letter-t" {...props}></Icon>
