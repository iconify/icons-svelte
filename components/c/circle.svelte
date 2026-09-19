<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n100scbgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n100scbgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:circle" {...props}></Icon>
