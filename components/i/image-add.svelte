<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2i8c-38t.css';
import '../../css/v/viznwcc0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h2i8c-38t"/><path class="viznwcc0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:image-add" {...props}></Icon>
