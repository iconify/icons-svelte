<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0_qcbctw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f0_qcbctw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:plurk-logo-1-alternate-block" {...props}></Icon>
