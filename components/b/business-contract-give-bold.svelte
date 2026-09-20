<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oej-_gbmt.css';
import '../../css/e/ezxsfzb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oej-_gbmt"/><path class="ezxsfzb4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:business-contract-give-bold" {...props}></Icon>
