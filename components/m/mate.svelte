<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-4y38biw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v-4y38biw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:mate" {...props}></Icon>
