<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eurq1d2or.css';
import '../../css/t/tav9lxblw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="eurq1d2or"/><path class="tav9lxblw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:key-o" {...props}></Icon>
