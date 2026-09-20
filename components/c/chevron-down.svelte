<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzy3gmb2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jzy3gmb2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:chevron-down" {...props}></Icon>
