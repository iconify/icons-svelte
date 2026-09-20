<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvs3lxber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nvs3lxber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:home-2-line" {...props}></Icon>
