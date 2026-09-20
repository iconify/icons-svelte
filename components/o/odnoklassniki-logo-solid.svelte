<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9djkebwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e9djkebwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:odnoklassniki-logo-solid" {...props}></Icon>
