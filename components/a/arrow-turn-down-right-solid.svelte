<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0apkjbjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k0apkjbjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-turn-down-right-solid" {...props}></Icon>
