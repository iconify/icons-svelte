<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3mass4yc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3mass4yc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:room-service-solid" {...props}></Icon>
