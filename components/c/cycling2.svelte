<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpib5khjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hpib5khjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:cycling2" {...props}></Icon>
