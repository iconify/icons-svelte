<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oci9svhqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oci9svhqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:lock-open-filled" {...props}></Icon>
