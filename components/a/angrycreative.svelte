<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8yq56beu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="w8yq56beu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:angrycreative" {...props}></Icon>
