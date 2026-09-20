<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcfszjblz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tcfszjblz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:check-read-bold" {...props}></Icon>
