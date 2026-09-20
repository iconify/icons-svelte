<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae1bp_7og.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ae1bp_7og"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:feathub-logo-solid" {...props}></Icon>
