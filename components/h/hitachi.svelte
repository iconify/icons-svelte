<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbvone-jk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jbvone-jk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:hitachi" {...props}></Icon>
