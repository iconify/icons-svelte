<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl4bbtw5c.css';
import '../../css/y/ynwkrvbew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nl4bbtw5c"/><path class="ynwkrvbew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:double-alt-arrow-left-bold" {...props}></Icon>
