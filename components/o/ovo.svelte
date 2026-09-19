<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owmzy3k6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="owmzy3k6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ovo" {...props}></Icon>
