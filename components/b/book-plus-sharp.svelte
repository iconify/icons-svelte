<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6a78ihov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e6a78ihov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:book-plus-sharp" {...props}></Icon>
