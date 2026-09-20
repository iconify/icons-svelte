<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drxa8yvrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="drxa8yvrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:netto" {...props}></Icon>
