<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apbgmyb7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5,"top":-7};
const content = `<path class="apbgmyb7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:check" {...props}></Icon>
