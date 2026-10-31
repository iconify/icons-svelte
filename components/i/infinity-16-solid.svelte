<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0c-dyboh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="o0c-dyboh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:infinity-16-solid" {...props}></Icon>
