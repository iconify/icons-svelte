<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzg80bc2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hzg80bc2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:jackett-light" {...props}></Icon>
