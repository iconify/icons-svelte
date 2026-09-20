<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7w6s7b2e.css';
import '../../css/v/v5pqt5bwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="b7w6s7b2e"/><path class="v5pqt5bwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:call-missed-16" {...props}></Icon>
