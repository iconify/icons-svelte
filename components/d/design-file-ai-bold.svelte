<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjplskbvx.css';
import '../../css/s/s-s3ptbcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qjplskbvx"/><path class="s-s3ptbcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:design-file-ai-bold" {...props}></Icon>
