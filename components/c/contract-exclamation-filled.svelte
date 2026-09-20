<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjbj8lbqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mjbj8lbqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:contract-exclamation-filled" {...props}></Icon>
