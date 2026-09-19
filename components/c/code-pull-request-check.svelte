<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qx40939my.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qx40939my"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:code-pull-request-check" {...props}></Icon>
