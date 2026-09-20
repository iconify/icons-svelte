<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szv9ucwib.css';
import '../../css/x/xenb14b2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="szv9ucwib"/><path class="xenb14b2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:home-security-lock-fill" {...props}></Icon>
