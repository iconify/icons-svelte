<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1dg0mbdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z1dg0mbdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:apache-netbeans-logo-solid" {...props}></Icon>
