<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ky9lh9bsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ky9lh9bsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:grid-solid" {...props}></Icon>
