<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jil-187ok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-3};
const content = `<path class="jil-187ok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:calendar-alt-f" {...props}></Icon>
