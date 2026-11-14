<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7ih7z60z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x7ih7z60z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:logout-02" {...props}></Icon>
