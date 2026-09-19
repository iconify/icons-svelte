<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5xop5b8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o5xop5b8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:folder-upload" {...props}></Icon>
