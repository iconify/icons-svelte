<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs5zptt1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xs5zptt1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:halloween-candy" {...props}></Icon>
