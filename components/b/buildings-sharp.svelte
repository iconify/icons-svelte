<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zyde15b2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zyde15b2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:buildings-sharp" {...props}></Icon>
