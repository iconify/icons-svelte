<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0n9b51wa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="o0n9b51wa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:float-left-solid" {...props}></Icon>
