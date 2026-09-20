<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4qxjab_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j4qxjab_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:diagonal-line-arrow-2-remix" {...props}></Icon>
