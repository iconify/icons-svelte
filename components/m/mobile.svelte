<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/astt8vb3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="astt8vb3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:mobile" {...props}></Icon>
