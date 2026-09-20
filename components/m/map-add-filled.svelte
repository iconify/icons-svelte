<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx0an_mmx.css';
import '../../css/s/spq8jsdzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tx0an_mmx"/><path class="spq8jsdzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:map-add-filled" {...props}></Icon>
