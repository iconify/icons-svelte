<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlxpj_2iq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qlxpj_2iq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:desktop-outline" {...props}></Icon>
