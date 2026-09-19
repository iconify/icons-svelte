<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zc84q5bnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zc84q5bnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:next" {...props}></Icon>
