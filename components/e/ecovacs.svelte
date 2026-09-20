<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6ig7kb0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v6ig7kb0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:ecovacs" {...props}></Icon>
