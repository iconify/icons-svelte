<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpz-9jmja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="dpz-9jmja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-left-right-circle" {...props}></Icon>
