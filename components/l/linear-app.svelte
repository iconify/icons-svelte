<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sso5dzmhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sso5dzmhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:linear-app" {...props}></Icon>
