<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9-n5-bxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-1,"top":-3};
const content = `<path class="t9-n5-bxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:fast-forward" {...props}></Icon>
