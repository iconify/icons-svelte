<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qz3_bd5iw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qz3_bd5iw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:eye-fill" {...props}></Icon>
