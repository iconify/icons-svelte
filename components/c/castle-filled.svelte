<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mi0s3acun.css';
import '../../css/w/w_ul5gqcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mi0s3acun"/><path class="w_ul5gqcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:castle-filled" {...props}></Icon>
