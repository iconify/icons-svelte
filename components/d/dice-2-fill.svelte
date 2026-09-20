<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_cgil99b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m_cgil99b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:dice-2-fill" {...props}></Icon>
