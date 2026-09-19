<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2q6mpbnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j2q6mpbnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:georgian-lari" {...props}></Icon>
