<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yox6y9bmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yox6y9bmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:angry2" {...props}></Icon>
