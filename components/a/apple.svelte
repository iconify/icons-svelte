<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gf9kq2bup.css';
import '../../css/w/wmtrl-rww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gf9kq2bup"/><path class="wmtrl-rww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:apple" {...props}></Icon>
