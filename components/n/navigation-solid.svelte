<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-6zgrbnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-6zgrbnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:navigation-solid" {...props}></Icon>
