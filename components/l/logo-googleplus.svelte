<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twias7bgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="twias7bgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:logo-googleplus" {...props}></Icon>
