<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpk53t-ak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kpk53t-ak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:package-arrow-down-sharp" {...props}></Icon>
