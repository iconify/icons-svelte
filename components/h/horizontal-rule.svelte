<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8fzx0j8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":10,"height":16};
const content = `<path class="k8fzx0j8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:horizontal-rule" {...props}></Icon>
