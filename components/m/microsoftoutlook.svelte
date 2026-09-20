<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gem936ssu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gem936ssu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:microsoftoutlook" {...props}></Icon>
