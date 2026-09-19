<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/reb798bgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="reb798bgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:meh-blank-filled" {...props}></Icon>
