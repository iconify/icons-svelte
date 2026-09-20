<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qogfksa1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qogfksa1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:kick-logo-logo-solid" {...props}></Icon>
