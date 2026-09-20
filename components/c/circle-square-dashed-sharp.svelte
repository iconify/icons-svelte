<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnk_77b9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnk_77b9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-square-dashed-sharp" {...props}></Icon>
