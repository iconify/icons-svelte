<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bj937vb0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bj937vb0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:chair-2-remix" {...props}></Icon>
