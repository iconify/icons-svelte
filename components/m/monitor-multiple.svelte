<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gn56tt2qg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gn56tt2qg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:monitor-multiple" {...props}></Icon>
