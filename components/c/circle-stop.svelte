<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yc48rr7mb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yc48rr7mb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:circle-stop" {...props}></Icon>
