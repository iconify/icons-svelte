<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nuxb7lb7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nuxb7lb7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:battery-100-solid" {...props}></Icon>
