<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9l716tmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v9l716tmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-left-up-bold" {...props}></Icon>
