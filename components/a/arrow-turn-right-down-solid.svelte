<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qypm3zu-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qypm3zu-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-turn-right-down-solid" {...props}></Icon>
