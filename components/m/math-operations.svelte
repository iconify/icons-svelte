<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvopj_b_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="uvopj_b_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:math-operations" {...props}></Icon>
