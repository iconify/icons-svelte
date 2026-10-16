<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6veld26c.css';
import '../../css/u/u_6gs2b2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y6veld26c"/><path class="u_6gs2b2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dosimeter-20" {...props}></Icon>
