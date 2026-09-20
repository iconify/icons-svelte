<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8v2ygp9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m8v2ygp9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-zeit" {...props}></Icon>
