<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3k7it36g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n3k7it36g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:exclamation-triangle" {...props}></Icon>
