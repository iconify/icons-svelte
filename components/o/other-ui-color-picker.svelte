<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mv0p_bjuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mv0p_bjuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:other-ui-color-picker" {...props}></Icon>
