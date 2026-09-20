<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwydw2bhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gwydw2bhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:car-find-outline" {...props}></Icon>
