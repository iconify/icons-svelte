<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iz7sqrpkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="iz7sqrpkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:check-sm-20" {...props}></Icon>
