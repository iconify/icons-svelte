<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rt1hgbkfu.css';
import '../../css/t/tlvy8hbsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rt1hgbkfu"/><path class="tlvy8hbsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:eye" {...props}></Icon>
