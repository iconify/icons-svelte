<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ff6usbbft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ff6usbbft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:creditcard-fill" {...props}></Icon>
