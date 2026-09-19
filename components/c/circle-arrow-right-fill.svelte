<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsfyh9guo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bsfyh9guo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:circle-arrow-right-fill" {...props}></Icon>
