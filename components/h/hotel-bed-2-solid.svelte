<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_ce3cchd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m_ce3cchd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:hotel-bed-2-solid" {...props}></Icon>
