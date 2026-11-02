<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8ncn-msd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="z8ncn-msd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-curve-up-left-20-solid" {...props}></Icon>
