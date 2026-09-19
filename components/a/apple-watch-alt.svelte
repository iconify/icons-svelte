<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3t4hnbgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n3t4hnbgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:apple-watch-alt" {...props}></Icon>
