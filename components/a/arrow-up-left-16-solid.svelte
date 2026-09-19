<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n73m8acuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="n73m8acuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-up-left-16-solid" {...props}></Icon>
