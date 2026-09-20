<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ug_mu57hm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ug_mu57hm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:app-minus-sharp" {...props}></Icon>
