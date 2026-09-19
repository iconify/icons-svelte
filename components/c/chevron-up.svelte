<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smg3t6jju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="smg3t6jju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:chevron-up" {...props}></Icon>
