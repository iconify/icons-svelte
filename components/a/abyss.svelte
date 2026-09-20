<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nh5k_h5sj.css';
import '../../css/f/fw7m_cc5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nh5k_h5sj"/><path class="fw7m_cc5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:abyss" {...props}></Icon>
