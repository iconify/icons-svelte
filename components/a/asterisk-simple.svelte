<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rx9-o-b0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rx9-o-b0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:asterisk-simple" {...props}></Icon>
