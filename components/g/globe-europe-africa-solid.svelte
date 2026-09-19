<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1kgt-bhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x1kgt-bhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:globe-europe-africa-solid" {...props}></Icon>
