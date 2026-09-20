<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmvcj-yyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qmvcj-yyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:loom-logo-block" {...props}></Icon>
