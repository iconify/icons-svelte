<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vztivl34g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vztivl34g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:laundry-hand-wash-bold" {...props}></Icon>
