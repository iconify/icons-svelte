<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vo78k0b3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vo78k0b3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-azure" {...props}></Icon>
