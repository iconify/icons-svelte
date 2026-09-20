<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pn4a9db6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-1.5};
const content = `<path class="pn4a9db6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:bell-off" {...props}></Icon>
