<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c871etbzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c871etbzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-bar-to-left" {...props}></Icon>
