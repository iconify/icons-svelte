<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvo458bdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cvo458bdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:clock-12-filled" {...props}></Icon>
