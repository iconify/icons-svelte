<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gndrgobtu.css';
import '../../css/v/vagvi2bms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gndrgobtu"/><path class="vagvi2bms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:bookmarks-document-alternate-bold" {...props}></Icon>
