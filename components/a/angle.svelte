<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qidjb1rhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qidjb1rhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:angle" {...props}></Icon>
