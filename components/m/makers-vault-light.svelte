<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ou0tc8obk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ou0tc8obk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:makers-vault-light" {...props}></Icon>
