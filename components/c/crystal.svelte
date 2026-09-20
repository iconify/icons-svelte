<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5l26jbbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n5l26jbbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:crystal" {...props}></Icon>
