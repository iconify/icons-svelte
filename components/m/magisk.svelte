<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jznvnct7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jznvnct7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:magisk" {...props}></Icon>
