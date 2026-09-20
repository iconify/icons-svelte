<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltnu138lr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ltnu138lr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:clock-ten" {...props}></Icon>
