<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3_jp68jm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k3_jp68jm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:arrow-local-axes" {...props}></Icon>
