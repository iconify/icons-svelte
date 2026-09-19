<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcv_oxbkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="zcv_oxbkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:house-buildings-small" {...props}></Icon>
