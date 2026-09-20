<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um39my9-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="um39my9-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:mirror-24" {...props}></Icon>
