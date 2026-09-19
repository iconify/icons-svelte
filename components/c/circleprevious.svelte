<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nehs0xbtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nehs0xbtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circleprevious" {...props}></Icon>
