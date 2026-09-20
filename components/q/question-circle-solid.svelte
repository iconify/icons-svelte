<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6dnf7-nj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x6dnf7-nj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:question-circle-solid" {...props}></Icon>
