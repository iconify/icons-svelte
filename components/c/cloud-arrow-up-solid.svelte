<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5i95fbbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n5i95fbbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:cloud-arrow-up-solid" {...props}></Icon>
