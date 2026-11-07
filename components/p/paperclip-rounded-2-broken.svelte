<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zx93v9xsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zx93v9xsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:paperclip-rounded-2-broken" {...props}></Icon>
