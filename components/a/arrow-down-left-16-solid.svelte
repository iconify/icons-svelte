<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie5rf59dn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ie5rf59dn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-down-left-16-solid" {...props}></Icon>
