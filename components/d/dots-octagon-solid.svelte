<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smzmz7blm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="smzmz7blm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:dots-octagon-solid" {...props}></Icon>
