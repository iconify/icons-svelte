<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec2m1t97f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ec2m1t97f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:git-fork-solid" {...props}></Icon>
