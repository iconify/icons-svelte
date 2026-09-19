<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0jzxob9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x0jzxob9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-turn-down-right" {...props}></Icon>
