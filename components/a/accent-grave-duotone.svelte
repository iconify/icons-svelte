<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfaxgkbqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jfaxgkbqy primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:accent-grave-duotone" {...props}></Icon>
