<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjnuvrbls.css';
import '../../css/o/oco7h52sv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="cjnuvrbls"/><path class="oco7h52sv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:bring-to-back-16" {...props}></Icon>
