<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-od26b1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v-od26b1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:code-of-conduct-16" {...props}></Icon>
