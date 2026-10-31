<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-5a6yozc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="v-5a6yozc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:crown-16-solid" {...props}></Icon>
