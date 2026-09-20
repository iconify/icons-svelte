<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjb9y5b-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zjb9y5b-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:linkedin-logo-solid" {...props}></Icon>
