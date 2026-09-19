<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmih6vbrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="gmih6vbrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:pineapple" {...props}></Icon>
