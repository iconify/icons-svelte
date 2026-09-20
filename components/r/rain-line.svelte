<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wp0adw4nv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wp0adw4nv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rain-line" {...props}></Icon>
