<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5w19n5ux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c5w19n5ux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:live-fill" {...props}></Icon>
