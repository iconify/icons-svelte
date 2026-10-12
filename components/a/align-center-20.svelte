<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti8yumbzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ti8yumbzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:align-center-20" {...props}></Icon>
