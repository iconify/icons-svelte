<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgpeqgbme.css';
import '../../css/b/bsih12bdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xgpeqgbme"/><path class="bsih12bdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:cursor-arrow-duotone" {...props}></Icon>
