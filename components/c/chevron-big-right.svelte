<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_isbacso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j_isbacso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:chevron-big-right" {...props}></Icon>
