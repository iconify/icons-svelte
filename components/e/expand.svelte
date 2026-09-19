<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5kfwsb7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="c5kfwsb7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:expand" {...props}></Icon>
