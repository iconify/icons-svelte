<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kz7vauv-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kz7vauv-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:delete-back-line" {...props}></Icon>
