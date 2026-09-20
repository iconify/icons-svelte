<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jms3h7bvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jms3h7bvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:news-paper-solid" {...props}></Icon>
