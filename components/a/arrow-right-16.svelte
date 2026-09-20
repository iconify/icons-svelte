<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqm-m2bem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dqm-m2bem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:arrow-right-16" {...props}></Icon>
