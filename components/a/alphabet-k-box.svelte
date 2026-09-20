<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcsh5bbkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jcsh5bbkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alphabet-k-box" {...props}></Icon>
