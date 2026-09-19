<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zr-j5cbkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zr-j5cbkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:knife-02" {...props}></Icon>
