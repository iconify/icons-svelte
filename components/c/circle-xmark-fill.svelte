<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yca151kvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yca151kvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:circle-xmark-fill" {...props}></Icon>
