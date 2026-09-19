<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kelnhhbkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1026,"height":1026};
const content = `<path class="kelnhhbkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:coffeebean" {...props}></Icon>
