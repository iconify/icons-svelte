<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-9k58bce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q-9k58bce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:mubi-logo-block" {...props}></Icon>
