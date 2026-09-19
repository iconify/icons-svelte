<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/my1rp3rmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="my1rp3rmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:arrow-up" {...props}></Icon>
