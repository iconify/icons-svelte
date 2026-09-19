<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szrkq1uqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="szrkq1uqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:arrows-shrink-h" {...props}></Icon>
