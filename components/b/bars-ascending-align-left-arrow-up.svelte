<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zl9ltt5qx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zl9ltt5qx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:bars-ascending-align-left-arrow-up" {...props}></Icon>
