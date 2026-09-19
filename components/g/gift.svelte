<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oatn87bvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oatn87bvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:gift" {...props}></Icon>
