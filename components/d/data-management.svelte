<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iiq3suo0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="iiq3suo0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:data-management" {...props}></Icon>
