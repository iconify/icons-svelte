<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hanj1gb4h.css';
import '../../css/e/egoxdachk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hanj1gb4h"/><path class="egoxdachk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-washer" {...props}></Icon>
