<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgy647b3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zgy647b3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:facebook-fill" {...props}></Icon>
