<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edesw8bbn.css';
import '../../css/p/p7k_3ybxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="edesw8bbn"/><path class="p7k_3ybxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-out-right-stroke-circle-half" {...props}></Icon>
