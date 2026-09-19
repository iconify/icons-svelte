<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ni6jdebub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="ni6jdebub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:money-bill-alt" {...props}></Icon>
