<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b38r9evhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b38r9evhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:elasticsearch" {...props}></Icon>
