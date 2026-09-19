<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg81je4wm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jg81je4wm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:options" {...props}></Icon>
