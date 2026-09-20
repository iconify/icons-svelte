<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkfr-acjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qkfr-acjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:moonbase-alpha" {...props}></Icon>
