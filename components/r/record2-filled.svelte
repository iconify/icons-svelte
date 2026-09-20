<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nm4a5uuyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nm4a5uuyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:record2-filled" {...props}></Icon>
