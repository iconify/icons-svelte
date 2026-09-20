<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/za7vhlb5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="za7vhlb5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:minutemailer" {...props}></Icon>
