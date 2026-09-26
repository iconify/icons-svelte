<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q268_fbou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q268_fbou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panels-top-right-outline" {...props}></Icon>
