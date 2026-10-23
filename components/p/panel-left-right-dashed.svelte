<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbfaopxnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kbfaopxnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:panel-left-right-dashed" {...props}></Icon>
