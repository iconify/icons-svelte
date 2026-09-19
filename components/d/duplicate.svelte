<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/woxf9krmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="woxf9krmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:duplicate" {...props}></Icon>
