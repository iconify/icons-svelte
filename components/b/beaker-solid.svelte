<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtr5rhb9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xtr5rhb9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:beaker-solid" {...props}></Icon>
