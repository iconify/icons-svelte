<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lky_h52fv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lky_h52fv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:magnet" {...props}></Icon>
