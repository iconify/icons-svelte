<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/waxglib2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="waxglib2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:file-directory-fill-24" {...props}></Icon>
