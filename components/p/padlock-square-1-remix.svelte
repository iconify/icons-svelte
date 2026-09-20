<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ze9lr2bnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ze9lr2bnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:padlock-square-1-remix" {...props}></Icon>
