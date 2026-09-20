<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/os9vfvbwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="os9vfvbwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:bag-suitcase-4-solid" {...props}></Icon>
