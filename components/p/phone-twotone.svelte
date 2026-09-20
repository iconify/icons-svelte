<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7lyzw.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-62.css';
import '../../css/f/fill-to-0_3.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d7lyzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:phone-twotone" {...props}></Icon>
