<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngp646uqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":512};
const content = `<path class="ngp646uqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:ckeditor" {...props}></Icon>
