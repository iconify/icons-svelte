<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awz3i37uh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="awz3i37uh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:money-bag-gbp" {...props}></Icon>
