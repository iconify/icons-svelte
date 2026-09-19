<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hepm892ta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hepm892ta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:code-fork-alt" {...props}></Icon>
