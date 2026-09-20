<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec4zljb5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ec4zljb5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:inbox-favorite-remix" {...props}></Icon>
