<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz4gdgerv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oz4gdgerv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:document-arrow-up" {...props}></Icon>
