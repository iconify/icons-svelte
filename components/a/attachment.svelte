<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubm57g7cb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ubm57g7cb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:attachment" {...props}></Icon>
