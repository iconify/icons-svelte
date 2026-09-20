<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wamhf9-td.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wamhf9-td"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:arrow-up-right-24" {...props}></Icon>
