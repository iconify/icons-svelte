<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sov856baf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sov856baf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:abstract-incomplete" {...props}></Icon>
