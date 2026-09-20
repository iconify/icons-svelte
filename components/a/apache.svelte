<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1ixcvbvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a1ixcvbvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:apache" {...props}></Icon>
