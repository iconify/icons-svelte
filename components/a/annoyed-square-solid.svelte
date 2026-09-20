<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo4k8bv1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zo4k8bv1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:annoyed-square-solid" {...props}></Icon>
