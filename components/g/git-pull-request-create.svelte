<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8an-u_vy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l8an-u_vy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:git-pull-request-create" {...props}></Icon>
