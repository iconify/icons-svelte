<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjph9dmcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qjph9dmcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:northeast-southwest-line" {...props}></Icon>
