<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxsw_71mi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rxsw_71mi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:rockstar-games" {...props}></Icon>
