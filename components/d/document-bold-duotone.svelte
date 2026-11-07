<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4w_uybke.css';
import '../../css/a/apggtqbru.css';
import '../../css/g/giaponbgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i4w_uybke"/><path class="apggtqbru"/><path class="giaponbgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:document-bold-duotone" {...props}></Icon>
