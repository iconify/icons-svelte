<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5kzytfkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="s5kzytfkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:lock-closed-16-solid" {...props}></Icon>
