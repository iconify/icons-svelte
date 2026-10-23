<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4my76bou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k4my76bou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:git-pull-request-create-arrow" {...props}></Icon>
