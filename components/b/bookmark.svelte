<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gl2t54zdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gl2t54zdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:bookmark" {...props}></Icon>
