<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjoympbtq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gjoympbtq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:play-list-check" {...props}></Icon>
