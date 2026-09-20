<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_ceh3bot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e_ceh3bot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:blood-bag-donation-remix" {...props}></Icon>
