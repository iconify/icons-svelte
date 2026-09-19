<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/puc5bd2pd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="puc5bd2pd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:new-session" {...props}></Icon>
