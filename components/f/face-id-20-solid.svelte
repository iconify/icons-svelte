<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4lf7envc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="c4lf7envc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:face-id-20-solid" {...props}></Icon>
