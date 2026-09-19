<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/muz8hiwra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="muz8hiwra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:photo-camera" {...props}></Icon>
