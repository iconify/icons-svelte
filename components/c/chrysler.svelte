<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dep_0wujp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dep_0wujp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:chrysler" {...props}></Icon>
