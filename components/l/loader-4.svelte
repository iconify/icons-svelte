<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cducd7zor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cducd7zor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:loader-4" {...props}></Icon>
