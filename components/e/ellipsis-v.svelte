<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kca43ld9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kca43ld9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:ellipsis-v" {...props}></Icon>
