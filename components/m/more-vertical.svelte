<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgdsu2bhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-9,"top":-2};
const content = `<path class="lgdsu2bhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:more-vertical" {...props}></Icon>
