<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5df2lbcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="s5df2lbcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:broadcast-signal" {...props}></Icon>
