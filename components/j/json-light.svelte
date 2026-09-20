<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-h0w2bcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-h0w2bcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:json-light" {...props}></Icon>
