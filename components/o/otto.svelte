<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/by-fq8dre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="by-fq8dre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:otto" {...props}></Icon>
