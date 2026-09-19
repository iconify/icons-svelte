<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uu1jccmbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b uu1jccmbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:motion-js" {...props}></Icon>
