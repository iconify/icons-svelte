<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7l9bcccv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t7l9bcccv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:content-new" {...props}></Icon>
