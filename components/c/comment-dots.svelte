<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afqsgacvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="afqsgacvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:comment-dots" {...props}></Icon>
