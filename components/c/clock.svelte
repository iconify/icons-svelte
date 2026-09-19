<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxghr-bvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="fxghr-bvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:clock" {...props}></Icon>
