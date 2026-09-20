<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0a_ztbxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g0a_ztbxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:book-open-alt" {...props}></Icon>
