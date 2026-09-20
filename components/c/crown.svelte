<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhrq_sy2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uhrq_sy2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:crown" {...props}></Icon>
