<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8ctk4-fb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k8ctk4-fb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:euro-square-solid" {...props}></Icon>
