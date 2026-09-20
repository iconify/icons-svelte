<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t63ypnw_i.css';
import '../../css/t/tw5hhubaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="t63ypnw_i"/><path class="tw5hhubaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:car" {...props}></Icon>
