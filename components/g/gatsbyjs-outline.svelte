<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tk3iaib_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tk3iaib_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:gatsbyjs-outline" {...props}></Icon>
