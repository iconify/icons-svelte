<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqg0eskzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eqg0eskzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:rooms-attic" {...props}></Icon>
