<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eguvsy.css';
import '../../css/k/kyznsp.css';
import '../../css/n/nz-btv.css';
import '../../css/s/so-from-22.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eguvsy kyznsp"/><path class="kyznsp nz-btv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:person-filled" {...props}></Icon>
