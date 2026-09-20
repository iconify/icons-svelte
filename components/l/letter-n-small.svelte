<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djkyirbhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="djkyirbhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:letter-n-small" {...props}></Icon>
