<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h68f7p_4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h68f7p_4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:budibase" {...props}></Icon>
