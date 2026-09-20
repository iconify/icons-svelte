<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obg_7yb7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="obg_7yb7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:line-arrow-turn-down-left-remix" {...props}></Icon>
