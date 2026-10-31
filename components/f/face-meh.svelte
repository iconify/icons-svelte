<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar7nh3bmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ar7nh3bmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:face-meh" {...props}></Icon>
