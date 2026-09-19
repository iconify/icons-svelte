<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybol07b_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ybol07b_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cloud-infra-migration" {...props}></Icon>
