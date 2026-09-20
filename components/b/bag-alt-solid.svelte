<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgrd1mbqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="qgrd1mbqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:bag-alt-solid" {...props}></Icon>
