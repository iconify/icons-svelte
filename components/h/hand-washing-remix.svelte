<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6zr-_tou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n6zr-_tou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:hand-washing-remix" {...props}></Icon>
