<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knmkkbbxd.css';
import '../../css/y/yp1z57b0r.css';
import '../../css/c/cep230_ho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="knmkkbbxd"/><path class="yp1z57b0r"/><path class="cep230_ho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:droplet" {...props}></Icon>
