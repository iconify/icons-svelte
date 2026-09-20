<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btm2enb5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4,"top":-1};
const content = `<path class="btm2enb5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:pocket-watch" {...props}></Icon>
