<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lg2tb8bko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lg2tb8bko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:notification-plus" {...props}></Icon>
