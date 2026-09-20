<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fq6ilubpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fq6ilubpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:battery-half" {...props}></Icon>
