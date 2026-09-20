<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7pzdsbat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n7pzdsbat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:email-open" {...props}></Icon>
