<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdb1m4bwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kdb1m4bwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:processor" {...props}></Icon>
