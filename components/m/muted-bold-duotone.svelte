<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nszf3hbuo.css';
import '../../css/m/m_773h0_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nszf3hbuo"/><path class="m_773h0_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:muted-bold-duotone" {...props}></Icon>
