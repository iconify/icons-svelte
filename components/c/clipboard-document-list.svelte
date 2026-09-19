<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpe9po6ap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dpe9po6ap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:clipboard-document-list" {...props}></Icon>
