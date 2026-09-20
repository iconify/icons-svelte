<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpkjzjbmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jpkjzjbmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pencil-question" {...props}></Icon>
