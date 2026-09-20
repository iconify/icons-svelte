<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bh45k69ub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bh45k69ub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:remove-favorite-highlight" {...props}></Icon>
