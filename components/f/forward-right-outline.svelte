<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdio18b-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pdio18b-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:forward-right-outline" {...props}></Icon>
