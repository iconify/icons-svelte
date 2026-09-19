<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9rqdccvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v9rqdccvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bolt-slash-16-solid" {...props}></Icon>
