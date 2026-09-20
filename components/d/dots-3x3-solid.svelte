<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ev10k0bqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ev10k0bqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:dots-3x3-solid" {...props}></Icon>
