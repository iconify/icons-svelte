<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-g3kgsag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-g3kgsag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pray" {...props}></Icon>
