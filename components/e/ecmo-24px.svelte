<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqe610a-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zqe610a-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:ecmo-24px" {...props}></Icon>
