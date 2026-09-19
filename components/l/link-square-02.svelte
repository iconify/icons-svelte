<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mox56qfok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mox56qfok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:link-square-02" {...props}></Icon>
