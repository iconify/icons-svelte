<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nf60hrb7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="nf60hrb7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-up-right-circle" {...props}></Icon>
