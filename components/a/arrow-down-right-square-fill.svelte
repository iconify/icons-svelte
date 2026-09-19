<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hutf_8bot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="hutf_8bot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-down-right-square-fill" {...props}></Icon>
