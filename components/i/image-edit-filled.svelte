<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/miig5dbtw.css';
import '../../css/d/dp_w-124f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="miig5dbtw"/><path class="dp_w-124f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:image-edit-filled" {...props}></Icon>
