<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mm2j-x-gc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="mm2j-x-gc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:phone-fill" {...props}></Icon>
