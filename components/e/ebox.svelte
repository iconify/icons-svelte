<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aq1585o-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aq1585o-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:ebox" {...props}></Icon>
