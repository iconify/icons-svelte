<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd0cbac6n.css';
import '../../css/y/yaf-d03di.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jd0cbac6n"/><path class="yaf-d03di"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:martial-arts-swords-bold" {...props}></Icon>
