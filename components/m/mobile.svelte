<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-532hvpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":24};
const content = `<path class="t-532hvpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:mobile" {...props}></Icon>
