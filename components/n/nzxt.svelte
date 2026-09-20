<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irhaz3qoz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="irhaz3qoz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nzxt" {...props}></Icon>
