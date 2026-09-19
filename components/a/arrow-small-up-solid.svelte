<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xg2-40p8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xg2-40p8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-small-up-solid" {...props}></Icon>
