<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8dx7ab2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v8dx7ab2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:credit-card" {...props}></Icon>
