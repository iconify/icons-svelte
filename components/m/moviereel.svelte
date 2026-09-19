<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucp01pb_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ucp01pb_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:moviereel" {...props}></Icon>
