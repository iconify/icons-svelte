<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y571l1bgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y571l1bgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:face-angry" {...props}></Icon>
