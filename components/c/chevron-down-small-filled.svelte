<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0rgs5y-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0rgs5y-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chevron-down-small-filled" {...props}></Icon>
