<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w809qnbsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w809qnbsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:dependabot" {...props}></Icon>
