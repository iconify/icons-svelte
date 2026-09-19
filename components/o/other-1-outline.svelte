<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykq3zccqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ykq3zccqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:other-1-outline" {...props}></Icon>
