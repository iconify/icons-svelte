<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9xc7hwgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v9xc7hwgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:relation-only-one-to-zero-or-many" {...props}></Icon>
