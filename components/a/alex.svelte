<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya5ldybze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":264,"height":512};
const content = `<path class="ya5ldybze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:alex" {...props}></Icon>
