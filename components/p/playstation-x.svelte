<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kepiutbkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kepiutbkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:playstation-x" {...props}></Icon>
