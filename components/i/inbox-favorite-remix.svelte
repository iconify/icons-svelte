<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fou3p8ybm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fou3p8ybm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:inbox-favorite-remix" {...props}></Icon>
