<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ki6tpkbda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ki6tpkbda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:battery-sharp" {...props}></Icon>
