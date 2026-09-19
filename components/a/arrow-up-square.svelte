<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh5z7f3dn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="lh5z7f3dn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-up-square" {...props}></Icon>
