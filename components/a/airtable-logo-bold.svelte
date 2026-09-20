<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am9l1u9bb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="am9l1u9bb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:airtable-logo-bold" {...props}></Icon>
