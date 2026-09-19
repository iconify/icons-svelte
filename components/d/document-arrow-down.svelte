<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtu4mioil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xtu4mioil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:document-arrow-down" {...props}></Icon>
