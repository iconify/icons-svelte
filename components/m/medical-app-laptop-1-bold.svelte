<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/euvxs1b3r.css';
import '../../css/e/ej65opbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="euvxs1b3r"/><path class="ej65opbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:medical-app-laptop-1-bold" {...props}></Icon>
