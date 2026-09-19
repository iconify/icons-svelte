<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj9y470xu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hj9y470xu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:cloud-clock-fill" {...props}></Icon>
