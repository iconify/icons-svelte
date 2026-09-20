<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukd2hu43u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ukd2hu43u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:git-compare-sharp" {...props}></Icon>
