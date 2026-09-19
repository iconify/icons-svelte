<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd66qbc5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fd66qbc5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:female-02" {...props}></Icon>
