<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t67dv2_bn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t67dv2_bn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:files" {...props}></Icon>
