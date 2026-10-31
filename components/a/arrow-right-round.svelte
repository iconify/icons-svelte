<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqel-rp7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kqel-rp7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-right-round" {...props}></Icon>
