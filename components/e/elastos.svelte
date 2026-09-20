<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qs7-zybgo.css';
import '../../css/h/hwwfh42ne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qs7-zybgo"/><path class="hwwfh42ne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:elastos" {...props}></Icon>
