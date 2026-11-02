<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yq_-j4dud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yq_-j4dud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-top-fill" {...props}></Icon>
