<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3qe4db5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v3qe4db5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:rectangle-stack" {...props}></Icon>
