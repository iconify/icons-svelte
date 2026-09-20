<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v65n5tbtm.css';
import '../../css/p/p06wdrbrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v65n5tbtm"/><path class="p06wdrbrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:reddit" {...props}></Icon>
