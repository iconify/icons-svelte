<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jaf_nb6xd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jaf_nb6xd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:equalizer" {...props}></Icon>
