<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krawmvbdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="krawmvbdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:mobile-phone-blackberry-2-bold" {...props}></Icon>
