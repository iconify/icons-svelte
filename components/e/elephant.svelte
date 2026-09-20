<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytm83wbxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ytm83wbxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:elephant" {...props}></Icon>
