<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tk315vbpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tk315vbpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cloud-fog-filled" {...props}></Icon>
