<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frrub2b7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="frrub2b7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:credit-card-disable-remix" {...props}></Icon>
