<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/voys5lbzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="voys5lbzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-bottom-left-on-square" {...props}></Icon>
