<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ro4bg4bvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ro4bg4bvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:link-question" {...props}></Icon>
