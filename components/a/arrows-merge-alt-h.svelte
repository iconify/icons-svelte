<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxw5baccr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jxw5baccr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:arrows-merge-alt-h" {...props}></Icon>
