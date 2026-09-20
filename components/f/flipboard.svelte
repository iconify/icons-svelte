<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-x2a3rsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b-x2a3rsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:flipboard" {...props}></Icon>
