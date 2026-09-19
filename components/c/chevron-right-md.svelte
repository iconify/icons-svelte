<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/du3re5bnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="du3re5bnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:chevron-right-md" {...props}></Icon>
