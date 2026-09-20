<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvxfjeb_u.css';
import '../../css/p/pi59231_r.css';
import '../../css/m/m1642jb7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gvxfjeb_u"/><path class="pi59231_r"/><path clip-rule="evenodd" class="m1642jb7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:purcentage-24" {...props}></Icon>
