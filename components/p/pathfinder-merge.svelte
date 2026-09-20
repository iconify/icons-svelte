<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_aws_4mp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l_aws_4mp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:pathfinder-merge" {...props}></Icon>
