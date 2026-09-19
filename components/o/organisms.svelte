<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z026_tbuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z026_tbuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:organisms" {...props}></Icon>
