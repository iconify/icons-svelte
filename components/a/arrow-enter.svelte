<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/piwl8bbyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="piwl8bbyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:arrow-enter" {...props}></Icon>
