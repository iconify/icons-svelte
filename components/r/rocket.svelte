<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhw5rd63a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bhw5rd63a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:rocket" {...props}></Icon>
