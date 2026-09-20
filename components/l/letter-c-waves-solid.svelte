<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ah9kv2bnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ah9kv2bnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-c-waves-solid" {...props}></Icon>
