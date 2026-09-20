<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9-9zsb3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w9-9zsb3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-left-up-linear" {...props}></Icon>
