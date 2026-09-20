<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6yow_htb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q6yow_htb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:amazon-luna-logo-solid" {...props}></Icon>
