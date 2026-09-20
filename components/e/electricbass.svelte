<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1ro2n2bt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="s1ro2n2bt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:electricbass" {...props}></Icon>
