<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie3p8absr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ie3p8absr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:remove-02" {...props}></Icon>
