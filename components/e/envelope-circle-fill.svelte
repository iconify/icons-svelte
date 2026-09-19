<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqh9-2boa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="tqh9-2boa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:envelope-circle-fill" {...props}></Icon>
