<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_bki1las.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o_bki1las"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:cakephp-old" {...props}></Icon>
