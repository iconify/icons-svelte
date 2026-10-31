<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffq2y69hk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ffq2y69hk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:chevron-down-up" {...props}></Icon>
