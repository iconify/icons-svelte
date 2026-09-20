<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j41jbxb6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j41jbxb6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:one-solid" {...props}></Icon>
