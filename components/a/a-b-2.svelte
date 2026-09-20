<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahr-1eb0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ahr-1eb0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:a-b-2" {...props}></Icon>
