<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qitrk6b8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qitrk6b8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:male-line" {...props}></Icon>
