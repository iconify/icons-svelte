<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3m_2pbzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v3m_2pbzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:overcast-logo-block" {...props}></Icon>
