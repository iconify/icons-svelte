<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljlho-brn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ljlho-brn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-turn-down-left" {...props}></Icon>
