<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwhd7bbup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bwhd7bbup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pdq" {...props}></Icon>
